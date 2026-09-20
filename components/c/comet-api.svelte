<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff1i7tbml.css';
import '../../css/k/kcxyz-btg.css';
import '../../css/t/to-4dx7tn.css';
import '../../css/x/xi3p24bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff1i7tbml"/><path class="kcxyz-btg"/><path class="to-4dx7tn"/><path class="xi3p24bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:comet-api" {...props}></Icon>
