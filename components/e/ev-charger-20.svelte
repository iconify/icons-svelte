<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgtsofb-b.css';
import '../../css/k/ke2j7bc4a.css';
import '../../css/o/o24sug9tq.css';
import '../../css/y/yjk-_bc4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kgtsofb-b"/><path class="ke2j7bc4a"/><path class="o24sug9tq"/><path class="yjk-_bc4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-charger-20" {...props}></Icon>
