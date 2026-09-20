<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhml_382w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhml_382w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:primereact" {...props}></Icon>
