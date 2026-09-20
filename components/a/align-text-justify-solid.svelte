<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k90ezdbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="k90ezdbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-text-justify-solid" {...props}></Icon>
