<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nonebkfri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nonebkfri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:remove-square-fill" {...props}></Icon>
