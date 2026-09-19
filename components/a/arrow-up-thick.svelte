<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opei0frxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opei0frxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-up-thick" {...props}></Icon>
