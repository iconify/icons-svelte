<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va8rt5bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="va8rt5bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:items-grid-small-24" {...props}></Icon>
