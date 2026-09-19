<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqcqgd4pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqcqgd4pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-cancel-alt" {...props}></Icon>
