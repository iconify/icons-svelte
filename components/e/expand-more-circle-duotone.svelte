<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e0ddc5bsu.css';
import '../../css/a/amzjcutka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e0ddc5bsu"/><path class="amzjcutka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-more-circle-duotone" {...props}></Icon>
