<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbgenzzof.css';
import '../../css/f/fu36ikuad.css';
import '../../css/u/u6-7e5-on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbgenzzof"/><path clip-rule="evenodd" class="fu36ikuad"/><path clip-rule="evenodd" class="u6-7e5-on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-line-bold" {...props}></Icon>
