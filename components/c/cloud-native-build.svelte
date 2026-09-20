<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx6sh7bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx6sh7bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloud-native-build" {...props}></Icon>
