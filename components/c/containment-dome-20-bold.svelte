<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxuo0cziq.css';
import '../../css/y/yfoxxnbix.css';
import '../../css/q/qu5dliood.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxuo0cziq"/><path class="yfoxxnbix"/><path class="qu5dliood"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:containment-dome-20-bold" {...props}></Icon>
