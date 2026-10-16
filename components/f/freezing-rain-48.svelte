<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv91ufroz.css';
import '../../css/y/y4teju86f.css';
import '../../css/k/kmncaq-ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kv91ufroz"/><path class="y4teju86f"/><path class="kmncaq-ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:freezing-rain-48" {...props}></Icon>
