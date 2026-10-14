<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/u/u59vj0byr.css';
import '../../css/l/lvkoenb9q.css';
import '../../css/z/z59nhccfv.css';
import '../../css/i/ipsrlibww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="u59vj0byr"/><path class="lvkoenb9q"/><path class="z59nhccfv"/><path class="ipsrlibww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:git-branch" {...props}></Icon>
