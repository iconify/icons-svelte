<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7wz0pbpw.css';
import '../../css/k/kbeh0tbto.css';
import '../../css/c/cn04bccyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7wz0pbpw"/><path class="kbeh0tbto"/><path class="cn04bccyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ling" {...props}></Icon>
