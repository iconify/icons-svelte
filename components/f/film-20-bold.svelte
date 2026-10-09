<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivpnqg4j.css';
import '../../css/u/uwqm8ubbj.css';
import '../../css/i/i2u0zab4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nivpnqg4j"/><path class="uwqm8ubbj"/><path class="i2u0zab4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:film-20-bold" {...props}></Icon>
