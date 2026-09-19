<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmg665juo.css';
import '../../css/o/odwst6b3m.css';
import '../../css/h/hb1bi3sso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmg665juo"/><rect class="odwst6b3m"/><rect class="hb1bi3sso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:between-horizontal-start-filled" {...props}></Icon>
