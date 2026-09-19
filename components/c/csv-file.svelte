<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugy8c7c-s.css';
import '../../css/h/hanozbgcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugy8c7c-s"/><path class="hanozbgcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:csv-file" {...props}></Icon>
