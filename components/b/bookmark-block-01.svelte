<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/ogtr9eflh.css';
import '../../css/o/o45e73ara.css';
import '../../css/c/cvx-s1b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ogtr9eflh"/><path class="o45e73ara"/><path class="cvx-s1b9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-block-01" {...props}></Icon>
