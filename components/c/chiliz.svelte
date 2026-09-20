<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tewny_bsl.css';
import '../../css/i/ichklriki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tewny_bsl"/><path clip-rule="evenodd" class="ichklriki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:chiliz" {...props}></Icon>
