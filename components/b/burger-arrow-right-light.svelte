<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee65k1lyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee65k1lyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger-arrow-right-light" {...props}></Icon>
