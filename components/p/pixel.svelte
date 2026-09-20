<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgavekyxp.css';
import '../../css/b/bop73y1vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgavekyxp"/><path class="bop73y1vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pixel" {...props}></Icon>
