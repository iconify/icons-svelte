<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlpsj4bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlpsj4bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:contacts-sharp" {...props}></Icon>
