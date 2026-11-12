<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-3vrkbik.css';
import '../../css/b/b3xfc2b-l.css';
import '../../css/j/j_dfhbbfa.css';
import '../../css/i/i43tj_8lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-3vrkbik"/><path class="b3xfc2b-l"/><path class="j_dfhbbfa"/><path class="i43tj_8lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nodemailer-light" {...props}></Icon>
