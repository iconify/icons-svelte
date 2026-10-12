<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjmjq831a.css';
import '../../css/z/z1o2t68zu.css';
import '../../css/t/tok4elbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bjmjq831a"/><path class="z1o2t68zu"/><path class="tok4elbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cash-register-20" {...props}></Icon>
