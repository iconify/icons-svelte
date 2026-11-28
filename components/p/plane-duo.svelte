<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lskr6z3ls.css';
import '../../css/i/ius8nukxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lskr6z3ls secondary"/><path class="ius8nukxs primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plane-duo" {...props}></Icon>
