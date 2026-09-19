<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6zz21_5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v6zz21_5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:comments" {...props}></Icon>
