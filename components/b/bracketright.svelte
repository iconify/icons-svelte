<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzlup_paf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":168,"height":954};
const content = `<path class="zzlup_paf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:bracketright" {...props}></Icon>
