<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k57yldbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k57yldbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-trans-solid" {...props}></Icon>
