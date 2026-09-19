<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/um27ogbzd.css';
import '../../css/o/ol6ywj3wc.css';
import '../../css/k/k0jum4blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="um27ogbzd"/><path class="ol6ywj3wc"/><path class="k0jum4blu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:clock-rotate-right" {...props}></Icon>
