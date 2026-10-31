<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_m51orpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x_m51orpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-down-up-16-solid" {...props}></Icon>
