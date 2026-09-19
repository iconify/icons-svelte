<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewe7up6bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewe7up6bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:currency-dollar" {...props}></Icon>
