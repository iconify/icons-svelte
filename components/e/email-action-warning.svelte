<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fll0uqb6i.css';
import '../../css/u/uipprnk6p.css';
import '../../css/k/kwnyzqbsp.css';
import '../../css/c/cj9sq2bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fll0uqb6i"/><path class="uipprnk6p"/><path class="kwnyzqbsp"/><path class="cj9sq2bnh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:email-action-warning" {...props}></Icon>
