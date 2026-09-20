<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deegn0b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="deegn0b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-less-square-fill" {...props}></Icon>
