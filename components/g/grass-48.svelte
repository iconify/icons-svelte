<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwrb__blp.css';
import '../../css/m/m_hycyb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pwrb__blp"/><path class="m_hycyb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grass-48" {...props}></Icon>
