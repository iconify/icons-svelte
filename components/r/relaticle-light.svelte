<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcjxjtqun.css';
import '../../css/g/gu5zfccqw.css';
import '../../css/x/x9gx-7buw.css';
import '../../css/z/z-uhu55bb.css';
import '../../css/n/n-srp4bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcjxjtqun"/><path class="gu5zfccqw"/><path class="x9gx-7buw"/><path class="z-uhu55bb"/><path class="n-srp4bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relaticle-light" {...props}></Icon>
