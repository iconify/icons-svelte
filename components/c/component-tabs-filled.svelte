<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl_bdxm0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yl_bdxm0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:component-tabs-filled" {...props}></Icon>
