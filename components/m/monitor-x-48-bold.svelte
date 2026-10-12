<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vitunp1ja.css';
import '../../css/p/phox42bnd.css';
import '../../css/m/ms4k0rbjg.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vitunp1ja"/><path class="phox42bnd"/><path class="ms4k0rbjg"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-x-48-bold" {...props}></Icon>
