<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_5eepoak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_5eepoak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-top-left" {...props}></Icon>
