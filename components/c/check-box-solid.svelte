<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vafs9rb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vafs9rb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:check-box-solid" {...props}></Icon>
