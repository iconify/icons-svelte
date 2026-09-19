<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lruz6gbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lruz6gbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:menu-alt-04" {...props}></Icon>
