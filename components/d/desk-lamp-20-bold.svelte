<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej4e03boz.css';
import '../../css/p/peoqhybmg.css';
import '../../css/e/ex0yribym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ej4e03boz"/><path class="peoqhybmg"/><path class="ex0yribym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desk-lamp-20-bold" {...props}></Icon>
