<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w84vznkgo.css';
import '../../css/i/idwhcabqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w84vznkgo"/><path class="idwhcabqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:invert-mode" {...props}></Icon>
