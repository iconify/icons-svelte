<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m85fekbws.css';
import '../../css/z/z6n_ozb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="m85fekbws"/><path class="z6n_ozb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-social-services" {...props}></Icon>
