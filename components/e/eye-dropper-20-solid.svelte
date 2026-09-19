<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqx63bc5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hqx63bc5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:eye-dropper-20-solid" {...props}></Icon>
