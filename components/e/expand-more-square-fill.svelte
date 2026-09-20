<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piv6exxub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="piv6exxub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:expand-more-square-fill" {...props}></Icon>
