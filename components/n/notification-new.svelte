<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2pr_9bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2pr_9bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification-new" {...props}></Icon>
