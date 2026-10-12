<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt9zz1bdg.css';
import '../../css/k/k0w0kweqa.css';
import '../../css/j/j3bulgbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tt9zz1bdg"/><path class="k0w0kweqa"/><path class="j3bulgbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drum-48-bold" {...props}></Icon>
