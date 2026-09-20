<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/v6f3rhfdf.css';
import '../../css/f/f_362pbxn.css';
import '../../css/g/gp0egaclj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v6f3rhfdf"/><circle class="f_362pbxn"/><circle class="gp0egaclj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:locate-fixed" {...props}></Icon>
