<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/e/eqnauu.css';
import '../../css/c/cmd1at.css';
import '../../css/t/tv0h4f.css';
import '../../css/s/so-from-48.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c eqnauu"/><circle class="cmd1at"/><path class="a0m25c tv0h4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:map-marker-minus" {...props}></Icon>
