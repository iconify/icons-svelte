<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqldz6btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqldz6btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:eject-outline" {...props}></Icon>
