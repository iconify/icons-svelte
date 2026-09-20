<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/y1kbuqzpw.css';
import '../../css/q/q2sdytbvw.css';
import '../../css/u/u3qj96b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><ellipse class="y1kbuqzpw"/><path class="q2sdytbvw"/><path class="u3qj96b3u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:coins-stack" {...props}></Icon>
