<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7y8yu2wv.css';
import '../../css/z/zco63dbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7y8yu2wv"/><path class="zco63dbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:netlify" {...props}></Icon>
