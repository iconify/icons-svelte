<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oha6nqbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oha6nqbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-3-filled" {...props}></Icon>
