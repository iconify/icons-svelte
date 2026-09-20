<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glkmpbbmk.css';
import '../../css/m/m4wlqkz7z.css';
import '../../css/o/o2k6b7btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glkmpbbmk"/><path class="m4wlqkz7z"/><path class="o2k6b7btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:book-bookmark" {...props}></Icon>
