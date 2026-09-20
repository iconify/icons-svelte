<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5_3hdchp.css';
import '../../css/v/vlf_obbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5_3hdchp"/><path class="vlf_obbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mc" {...props}></Icon>
