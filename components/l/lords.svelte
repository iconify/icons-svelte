<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi8ew2bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xi8ew2bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lords" {...props}></Icon>
