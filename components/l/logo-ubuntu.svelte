<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiwcx9z6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uiwcx9z6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-ubuntu" {...props}></Icon>
