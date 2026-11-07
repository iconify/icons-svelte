<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g26s6eb5h.css';
import '../../css/z/zwlaz0b-f.css';
import '../../css/q/q3o58pbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g26s6eb5h"/><path class="zwlaz0b-f"/><path clip-rule="evenodd" class="q3o58pbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-5-outline" {...props}></Icon>
