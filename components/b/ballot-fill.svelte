<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz2-_obyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dz2-_obyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ballot-fill" {...props}></Icon>
