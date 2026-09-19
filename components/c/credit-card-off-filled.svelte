<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnx6itptw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnx6itptw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-off-filled" {...props}></Icon>
