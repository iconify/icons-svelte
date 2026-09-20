<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk4qgdbux.css';
import '../../css/t/tevsa0mrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk4qgdbux"/><path class="tevsa0mrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:music-circle-fill" {...props}></Icon>
