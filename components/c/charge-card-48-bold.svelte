<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmptwf-ti.css';
import '../../css/e/eq_morblf.css';
import '../../css/q/qntnywbvk.css';
import '../../css/w/wa3ofwbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jmptwf-ti"/><path class="eq_morblf"/><path class="qntnywbvk"/><path class="wa3ofwbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charge-card-48-bold" {...props}></Icon>
