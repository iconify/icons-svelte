<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxrer4n2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxrer4n2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:dental" {...props}></Icon>
