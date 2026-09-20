<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smt1xtbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smt1xtbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:pricetag-alt" {...props}></Icon>
