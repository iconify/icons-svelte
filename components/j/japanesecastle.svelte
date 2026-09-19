<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e906i-3ln.css';
import '../../css/i/i6zfmwblj.css';
import '../../css/k/kod42bcng.css';
import '../../css/p/pv2s4tb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e906i-3ln"/><path class="i6zfmwblj"/><path class="kod42bcng"/><path class="pv2s4tb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:japanesecastle" {...props}></Icon>
