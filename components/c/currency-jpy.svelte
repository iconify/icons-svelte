<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-j1u4azw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-j1u4azw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:currency-jpy" {...props}></Icon>
