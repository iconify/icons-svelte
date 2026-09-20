<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vtf5akbqv.css';
import '../../css/c/c37etu0ab.css';
import '../../css/w/w4e8dubxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vtf5akbqv"/><path class="c37etu0ab"/><path class="w4e8dubxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:blank-alt-duotone-line" {...props}></Icon>
