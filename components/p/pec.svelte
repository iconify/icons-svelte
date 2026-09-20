<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-mqnw-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-mqnw-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pec" {...props}></Icon>
