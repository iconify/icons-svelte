<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mau6vrbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mau6vrbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-office-2-16-solid" {...props}></Icon>
