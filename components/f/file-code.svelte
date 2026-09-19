<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9in7kr6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y9in7kr6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-code" {...props}></Icon>
