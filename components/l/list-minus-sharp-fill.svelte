<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojhdz2bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojhdz2bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-minus-sharp-fill" {...props}></Icon>
