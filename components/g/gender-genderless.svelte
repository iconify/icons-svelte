<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh336ri0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh336ri0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:gender-genderless" {...props}></Icon>
