<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbtlfqbcg.css';
import '../../css/q/qoc3rw04c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="kbtlfqbcg"/><path class="qoc3rw04c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-laboratory" {...props}></Icon>
