<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3he05zka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3he05zka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:money-bag-bold" {...props}></Icon>
