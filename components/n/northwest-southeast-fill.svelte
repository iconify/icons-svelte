<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ork6cbxuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ork6cbxuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:northwest-southeast-fill" {...props}></Icon>
