<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o38pqhu6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o38pqhu6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:acupuncture-4" {...props}></Icon>
