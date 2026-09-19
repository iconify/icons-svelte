<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1xy6nh9u.css';
import '../../css/d/dq12o7ykb.css';
import '../../css/b/b74ikwezj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="n1xy6nh9u"/><circle class="dq12o7ykb"/><circle class="b74ikwezj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:more-horizontal-fill" {...props}></Icon>
