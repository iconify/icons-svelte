<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st8y9r6ap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st8y9r6ap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:prescription" {...props}></Icon>
