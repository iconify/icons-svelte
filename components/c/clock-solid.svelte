<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2otw27pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2otw27pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:clock-solid" {...props}></Icon>
