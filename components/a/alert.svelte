<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gav6n2baw.css';
import '../../css/b/bl21z0b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="gav6n2baw"/><path class="bl21z0b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:alert" {...props}></Icon>
