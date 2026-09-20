<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b80592p_t.css';
import '../../css/b/b1k_d4bpa.css';
import '../../css/f/fpu345b5a.css';
import '../../css/i/i6_9ppfpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b80592p_t"/><path class="b1k_d4bpa"/><path class="fpu345b5a"/><path class="i6_9ppfpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:geeq" {...props}></Icon>
