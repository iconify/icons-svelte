<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k_we9dbkd.css';
import '../../css/q/qvv9bdbon.css';
import '../../css/n/n7lafqbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k_we9dbkd"/><path class="qvv9bdbon"/><path class="n7lafqbhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:danger" {...props}></Icon>
