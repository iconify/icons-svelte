<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmodlobup.css';
import '../../css/e/emd0dl2-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hmodlobup"/><path class="emd0dl2-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-card-48-bold" {...props}></Icon>
