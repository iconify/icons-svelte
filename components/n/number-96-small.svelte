<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyhkp7bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyhkp7bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-96-small" {...props}></Icon>
