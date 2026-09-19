<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui7et3t-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ui7et3t-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:notification-fill" {...props}></Icon>
