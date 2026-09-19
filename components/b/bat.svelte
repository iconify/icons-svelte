<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z0dprtbui.css';
import '../../css/v/vejlu9bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="z0dprtbui"/><path class="vejlu9bnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:bat" {...props}></Icon>
