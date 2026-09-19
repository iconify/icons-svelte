<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh9o9fbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh9o9fbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-plus-alt" {...props}></Icon>
