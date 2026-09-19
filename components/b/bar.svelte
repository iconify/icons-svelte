<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k38_ocq6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k38_ocq6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:bar" {...props}></Icon>
