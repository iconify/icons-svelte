<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wckr9kb1z.css';
import '../../css/k/kj34mfmgb.css';
import '../../css/o/oclompb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><path class="kj34mfmgb"/><circle class="oclompb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:question-mark-circle-outline" {...props}></Icon>
