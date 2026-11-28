<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyfe3ob5n.css';
import '../../css/h/hxxrwcb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yyfe3ob5n"/><path class="hxxrwcb9s primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ribbon-duo" {...props}></Icon>
