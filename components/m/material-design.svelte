<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pciruqb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pciruqb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:material-design" {...props}></Icon>
