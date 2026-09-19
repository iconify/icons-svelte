<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gngy5vaph.css';
import '../../css/q/qsez0nite.css';
import '../../css/e/e5jfj3b2v.css';
import '../../css/m/mfg1gacjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gngy5vaph"/><path class="qsez0nite"/><path class="e5jfj3b2v"/><path class="mfg1gacjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-validation-02" {...props}></Icon>
