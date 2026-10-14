<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx01pybcw.css';
import '../../css/g/go6el9bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx01pybcw"/><path class="go6el9bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:code-badge-24" {...props}></Icon>
