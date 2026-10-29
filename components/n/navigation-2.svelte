<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx-fqcbrz.css';
import '../../css/z/zyr9tjbek.css';
import '../../css/f/f1ge8bb-b.css';
import '../../css/h/haaxscqwv.css';
import '../../css/w/w23tfpzak.css';
import '../../css/l/liczzd6oq.css';
import '../../css/z/z3647b8sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx-fqcbrz wm-shadow"/><path class="zyr9tjbek"/><path class="f1ge8bb-b"/><path class="haaxscqwv"/><path class="w23tfpzak"/><path class="liczzd6oq wm-shine"/><path class="z3647b8sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-plush:navigation-2" {...props}></Icon>
