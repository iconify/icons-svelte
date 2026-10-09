<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apq2pw-va.css';
import '../../css/f/fjn5fnnqh.css';
import '../../css/x/xs7xk1ywk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="apq2pw-va"/><path class="fjn5fnnqh"/><path class="xs7xk1ywk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fan-20" {...props}></Icon>
