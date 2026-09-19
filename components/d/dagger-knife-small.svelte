<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvru_hbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fvru_hbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:dagger-knife-small" {...props}></Icon>
