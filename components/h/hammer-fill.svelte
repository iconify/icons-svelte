<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ld3lc5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5ld3lc5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hammer-fill" {...props}></Icon>
