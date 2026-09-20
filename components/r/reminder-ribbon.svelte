<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk6lyrbfc.css';
import '../../css/l/lpm14mvjr.css';
import '../../css/s/shxtxmbiv.css';
import '../../css/r/rcxz1fmas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="uk6lyrbfc"/><path class="lpm14mvjr"/><path class="shxtxmbiv"/><path class="rcxz1fmas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:reminder-ribbon" {...props}></Icon>
