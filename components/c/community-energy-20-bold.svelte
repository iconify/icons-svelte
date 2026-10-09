<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq1tynbis.css';
import '../../css/s/sq8u2euwj.css';
import '../../css/l/l6n_mmb1f.css';
import '../../css/u/u5tmx4bng.css';
import '../../css/u/uvemerbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dq1tynbis"/><path class="sq8u2euwj"/><path class="l6n_mmb1f"/><path class="u5tmx4bng"/><path class="uvemerbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:community-energy-20-bold" {...props}></Icon>
