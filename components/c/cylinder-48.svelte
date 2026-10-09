<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnku0e3st.css';
import '../../css/u/uc2ua4u2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gnku0e3st"/><path class="uc2ua4u2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cylinder-48" {...props}></Icon>
