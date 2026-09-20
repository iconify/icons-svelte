<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcxdw0blf.css';
import '../../css/r/rsc1xgbvj.css';
import '../../css/n/nno8gebdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcxdw0blf"/><path class="rsc1xgbvj"/><path class="nno8gebdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:acq" {...props}></Icon>
