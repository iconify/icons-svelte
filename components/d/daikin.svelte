<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avqxqmkpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avqxqmkpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:daikin" {...props}></Icon>
